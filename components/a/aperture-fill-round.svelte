<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ij2dpobuz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ij2dpobuz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:aperture-fill-round" {...props}></Icon>
