<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gv-8p8b2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gv-8p8b2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:pin-x" {...props}></Icon>
