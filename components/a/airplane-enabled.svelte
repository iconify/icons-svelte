<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3a_eqbui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="i3a_eqbui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:airplane-enabled" {...props}></Icon>
