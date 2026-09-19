<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wlgkx343y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="wlgkx343y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:logo-fl" {...props}></Icon>
