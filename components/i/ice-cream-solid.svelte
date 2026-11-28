<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn8cowbus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xn8cowbus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:ice-cream-solid" {...props}></Icon>
