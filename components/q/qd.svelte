<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0_jum4ti.css';
import '../../css/q/q6h8h4bzx.css';
import '../../css/t/txdkxnr7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z0_jum4ti"/><path class="q6h8h4bzx"/><path class="txdkxnr7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:qd" {...props}></Icon>
