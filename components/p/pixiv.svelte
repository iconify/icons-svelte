<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a2jrpnjac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="a2jrpnjac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:pixiv" {...props}></Icon>
