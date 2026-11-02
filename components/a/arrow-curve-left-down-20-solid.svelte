<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kx416_bvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="kx416_bvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:arrow-curve-left-down-20-solid" {...props}></Icon>
