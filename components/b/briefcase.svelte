<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lx0ln9bfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lx0ln9bfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:briefcase" {...props}></Icon>
