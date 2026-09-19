<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/miv52rbxg.css';
import '../../css/v/v_r2u0_pg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="miv52rbxg"/><path class="v_r2u0_pg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:microchip" {...props}></Icon>
