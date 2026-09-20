<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxfri69yb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mxfri69yb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:label-variant-outline" {...props}></Icon>
