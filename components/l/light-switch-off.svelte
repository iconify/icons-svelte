<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l44qhg_hc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l44qhg_hc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:light-switch-off" {...props}></Icon>
