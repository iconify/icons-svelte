<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/py5k_qboi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="py5k_qboi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:pet-grooming" {...props}></Icon>
