<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-j76dbhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m-j76dbhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:import-export-bold" {...props}></Icon>
