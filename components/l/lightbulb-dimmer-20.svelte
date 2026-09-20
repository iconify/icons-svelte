<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dfvs7j2dg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dfvs7j2dg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:lightbulb-dimmer-20" {...props}></Icon>
