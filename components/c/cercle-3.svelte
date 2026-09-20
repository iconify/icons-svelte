<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hd4a3wzlb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hd4a3wzlb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:cercle-3" {...props}></Icon>
