<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dh86xtb-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dh86xtb-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cast-audio" {...props}></Icon>
