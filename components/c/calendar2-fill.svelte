<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/igw-twc6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="igw-twc6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:calendar2-fill" {...props}></Icon>
