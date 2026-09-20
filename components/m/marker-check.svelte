<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/urm4i36ho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="urm4i36ho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:marker-check" {...props}></Icon>
