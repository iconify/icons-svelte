<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dz0y5abce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dz0y5abce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-home-circle" {...props}></Icon>
