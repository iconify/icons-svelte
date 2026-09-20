<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwwk0dnhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fwwk0dnhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:projector-screen-variant-outline" {...props}></Icon>
