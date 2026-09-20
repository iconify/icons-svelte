<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l07u-vb3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l07u-vb3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:edge-impulse" {...props}></Icon>
