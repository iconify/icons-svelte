<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jp5ux63gl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jp5ux63gl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-windows" {...props}></Icon>
