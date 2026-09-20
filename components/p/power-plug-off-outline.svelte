<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ick56cv-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ick56cv-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:power-plug-off-outline" {...props}></Icon>
