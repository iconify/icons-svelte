<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcgyn62ej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dcgyn62ej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:contract" {...props}></Icon>
