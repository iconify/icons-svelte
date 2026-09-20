<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fd9vq1gyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fd9vq1gyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:data-minus-line" {...props}></Icon>
