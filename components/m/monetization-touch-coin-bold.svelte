<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fk1yoeo-c.css';
import '../../css/i/i31-_h-xy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fk1yoeo-c"/><path class="i31-_h-xy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:monetization-touch-coin-bold" {...props}></Icon>
