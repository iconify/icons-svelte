<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/codh4ybyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="codh4ybyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:heart-pulse-check" {...props}></Icon>
