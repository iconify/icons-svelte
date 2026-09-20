<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yab7w5bww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yab7w5bww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:basic-arrows-up-left" {...props}></Icon>
