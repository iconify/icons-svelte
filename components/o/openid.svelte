<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxwat0yau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1023};
const content = `<path class="sxwat0yau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:openid" {...props}></Icon>
