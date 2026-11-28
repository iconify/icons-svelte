<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/poya7oh9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="poya7oh9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:door-lock" {...props}></Icon>
