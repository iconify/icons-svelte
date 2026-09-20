<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rs_hb49jg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rs_hb49jg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:coffee" {...props}></Icon>
