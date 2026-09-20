<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfpf-rs6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hfpf-rs6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:equalizer" {...props}></Icon>
