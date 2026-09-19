<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ke-vqfa8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ke-vqfa8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:adjustments-vertical-20-solid" {...props}></Icon>
