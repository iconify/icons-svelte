<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xebg60blc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xebg60blc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:minimize" {...props}></Icon>
