<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1j_o8nag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z1j_o8nag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:enter-duotone" {...props}></Icon>
