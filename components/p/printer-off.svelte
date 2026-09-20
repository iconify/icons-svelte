<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgcqbobdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hgcqbobdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:printer-off" {...props}></Icon>
