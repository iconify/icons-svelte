<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gva24ybfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gva24ybfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:aliasvault" {...props}></Icon>
