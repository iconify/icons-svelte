<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bljuvcbnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bljuvcbnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:argus-light" {...props}></Icon>
