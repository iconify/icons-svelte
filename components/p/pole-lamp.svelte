<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vo3u11b1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vo3u11b1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:pole-lamp" {...props}></Icon>
