<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uh1w0u0lc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uh1w0u0lc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:econt" {...props}></Icon>
