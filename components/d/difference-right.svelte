<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oaxtr4zwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oaxtr4zwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:difference-right" {...props}></Icon>
