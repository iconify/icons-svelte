<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4hv-9bcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f4hv-9bcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:bike-check" {...props}></Icon>
