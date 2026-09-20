<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zshbt6bzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zshbt6bzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:carousel-h-filled" {...props}></Icon>
