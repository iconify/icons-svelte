<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eddygeb4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eddygeb4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:import-check" {...props}></Icon>
