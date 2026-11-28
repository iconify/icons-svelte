<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gjfo7acdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gjfo7acdd primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:chart-network-duotone" {...props}></Icon>
