<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vg16eyxff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vg16eyxff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:oven-mitt" {...props}></Icon>
