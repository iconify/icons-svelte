<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h234xn1yb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h234xn1yb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:map-pin-question" {...props}></Icon>
