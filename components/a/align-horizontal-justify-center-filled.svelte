<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zngg8jbuz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zngg8jbuz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:align-horizontal-justify-center-filled" {...props}></Icon>
