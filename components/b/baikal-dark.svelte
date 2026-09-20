<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uq3xmi0yu.css';
import '../../css/n/nvqrqlbpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uq3xmi0yu"/><path class="nvqrqlbpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:baikal-dark" {...props}></Icon>
