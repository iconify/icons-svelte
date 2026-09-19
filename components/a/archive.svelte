<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nr5s66b4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nr5s66b4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:archive" {...props}></Icon>
