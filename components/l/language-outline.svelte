<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgwpwkbxm.css';
import '../../css/l/lz5trxqpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zgwpwkbxm"/><path class="lz5trxqpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:language-outline" {...props}></Icon>
