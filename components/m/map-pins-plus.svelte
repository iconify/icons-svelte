<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4i5kyb1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s4i5kyb1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:map-pins-plus" {...props}></Icon>
