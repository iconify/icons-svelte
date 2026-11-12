<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gbjl5x_qp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gbjl5x_qp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:forte-light" {...props}></Icon>
