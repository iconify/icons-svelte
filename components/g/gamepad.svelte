<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rh-ombyti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rh-ombyti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:gamepad" {...props}></Icon>
