<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_j5wtbxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h_j5wtbxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:logout-half-circle-line" {...props}></Icon>
