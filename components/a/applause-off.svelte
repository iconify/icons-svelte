<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwszk5ntc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mwszk5ntc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:applause-off" {...props}></Icon>
