<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yycsh22_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yycsh22_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:jumpto-expressive" {...props}></Icon>
