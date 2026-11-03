<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zfeohs2bk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zfeohs2bk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kept-inventory-dark" {...props}></Icon>
