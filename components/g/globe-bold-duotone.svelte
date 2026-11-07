<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fnuscxboo.css';
import '../../css/i/iik--rn3y.css';
import '../../css/j/jdp6hwbta.css';
import '../../css/g/gpifwzblh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="fnuscxboo"/><path class="iik--rn3y"/><path class="jdp6hwbta"/><path class="gpifwzblh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:globe-bold-duotone" {...props}></Icon>
