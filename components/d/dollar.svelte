<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0noedbih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r0noedbih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:dollar" {...props}></Icon>
