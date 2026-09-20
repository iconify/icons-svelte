<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kr5k10bfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kr5k10bfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:glide-g" {...props}></Icon>
