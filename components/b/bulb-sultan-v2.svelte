<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhgguqqyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hhgguqqyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:bulb-sultan-v2" {...props}></Icon>
