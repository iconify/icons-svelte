<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/anlkm7xov.css';
import '../../css/f/fbtcj0tzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="anlkm7xov"/><path class="fbtcj0tzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:alt-arrow-up-bold-duotone" {...props}></Icon>
