<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mg2zhxvfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mg2zhxvfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:hoymiles-inverter" {...props}></Icon>
