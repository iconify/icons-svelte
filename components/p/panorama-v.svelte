<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nf2eccnhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nf2eccnhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:panorama-v" {...props}></Icon>
