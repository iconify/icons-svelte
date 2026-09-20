<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/libznybin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="libznybin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:navy-federal-credit-union-light" {...props}></Icon>
