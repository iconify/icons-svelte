<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vblcbgz4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vblcbgz4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:felicloud-dark" {...props}></Icon>
