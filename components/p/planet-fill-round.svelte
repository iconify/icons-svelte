<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5ol58bln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z5ol58bln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:planet-fill-round" {...props}></Icon>
