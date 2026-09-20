<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wb86ohshj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wb86ohshj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:half-star-ltr" {...props}></Icon>
