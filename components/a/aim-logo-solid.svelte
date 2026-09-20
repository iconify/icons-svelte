<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jiat6mbef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jiat6mbef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:aim-logo-solid" {...props}></Icon>
