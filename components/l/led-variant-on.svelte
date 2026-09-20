<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nf8916bmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nf8916bmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:led-variant-on" {...props}></Icon>
