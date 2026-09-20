<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e042sdbga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e042sdbga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:battery-vertical-off" {...props}></Icon>
