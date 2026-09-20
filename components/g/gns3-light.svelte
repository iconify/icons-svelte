<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thwih6b_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="thwih6b_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:gns3-light" {...props}></Icon>
