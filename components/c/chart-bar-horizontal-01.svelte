<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gcyu-v6zp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gcyu-v6zp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:chart-bar-horizontal-01" {...props}></Icon>
