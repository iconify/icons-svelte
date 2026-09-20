<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dpho4dpti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dpho4dpti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:ip-network" {...props}></Icon>
