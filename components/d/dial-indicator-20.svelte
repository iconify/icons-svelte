<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1wkb86ze.css';
import '../../css/u/u6d9mwu4u.css';
import '../../css/y/y18icnb3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="y1wkb86ze"/><path class="u6d9mwu4u"/><path class="y18icnb3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:dial-indicator-20" {...props}></Icon>
