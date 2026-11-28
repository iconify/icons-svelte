<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g456qubjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g456qubjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:map-pin-minus" {...props}></Icon>
