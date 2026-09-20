<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdtiijb2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pdtiijb2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:invert-colors" {...props}></Icon>
