<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kg40_p8ml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kg40_p8ml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:cloud-upload" {...props}></Icon>
