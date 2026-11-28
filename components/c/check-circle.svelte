<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0vuqx_ps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d0vuqx_ps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:check-circle" {...props}></Icon>
