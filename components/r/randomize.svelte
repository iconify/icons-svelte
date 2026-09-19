<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2k_bn38y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="k2k_bn38y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:randomize" {...props}></Icon>
