<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pw4s_ccdv.css';
import '../../css/a/afxn0v40s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":25};
const content = `<path class="pw4s_ccdv"/><path class="afxn0v40s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:angle-double-down" {...props}></Icon>
