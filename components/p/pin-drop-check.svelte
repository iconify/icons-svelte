<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0p6_fbvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g0p6_fbvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:pin-drop-check" {...props}></Icon>
