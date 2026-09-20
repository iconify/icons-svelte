<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wsd-ij4-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wsd-ij4-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:lightbulb-variant-outline" {...props}></Icon>
