<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dn3mo9bss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dn3mo9bss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:pi-network" {...props}></Icon>
