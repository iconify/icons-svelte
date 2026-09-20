<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9187bsnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d9187bsnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ladder-dark" {...props}></Icon>
