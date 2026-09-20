<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_11pibqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="z_11pibqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:romance-heart-lock" {...props}></Icon>
