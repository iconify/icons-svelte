<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_oyrm6dw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l_oyrm6dw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:hexagon" {...props}></Icon>
