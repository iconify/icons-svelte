<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dco2sibti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dco2sibti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:fuel-check" {...props}></Icon>
