<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udzhtcbgx.css';
import '../../css/b/bneojtbom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="udzhtcbgx"/><path class="bneojtbom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:daylog" {...props}></Icon>
