<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4rob80ci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i4rob80ci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:arrow-up-square-fill" {...props}></Icon>
