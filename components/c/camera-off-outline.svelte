<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kx0uqebjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kx0uqebjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:camera-off-outline" {...props}></Icon>
