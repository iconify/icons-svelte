<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lavm11ltb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lavm11ltb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:drawing-compass" {...props}></Icon>
