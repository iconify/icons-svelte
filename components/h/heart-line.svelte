<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w29elplbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w29elplbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:heart-line" {...props}></Icon>
