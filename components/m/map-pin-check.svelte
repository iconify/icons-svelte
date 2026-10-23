<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hg33ixklt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hg33ixklt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:map-pin-check" {...props}></Icon>
