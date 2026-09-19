<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ki14w9bub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ki14w9bub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-camera-off" {...props}></Icon>
