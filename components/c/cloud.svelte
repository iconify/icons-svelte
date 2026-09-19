<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zy7sa5acr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zy7sa5acr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:cloud" {...props}></Icon>
