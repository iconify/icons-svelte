<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0y80gtpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o0y80gtpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:avatar-circle-sharp" {...props}></Icon>
