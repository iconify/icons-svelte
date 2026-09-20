<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iz75m85jy.css';
import '../../css/i/ipvgj6bpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iz75m85jy"/><path class="ipvgj6bpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:mic-solid" {...props}></Icon>
