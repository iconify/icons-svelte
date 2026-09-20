<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4pe5y8hf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k4pe5y8hf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:led-on" {...props}></Icon>
