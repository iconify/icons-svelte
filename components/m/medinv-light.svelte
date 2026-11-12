<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zh8ic0_ra.css';
import '../../css/j/jr3az-bvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zh8ic0_ra"/><circle class="jr3az-bvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:medinv-light" {...props}></Icon>
