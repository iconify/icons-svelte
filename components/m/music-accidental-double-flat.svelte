<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3_th3lrr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q3_th3lrr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:music-accidental-double-flat" {...props}></Icon>
