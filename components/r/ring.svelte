<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdj_qdb8q.css';
import '../../css/l/lhh1z-yfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kdj_qdb8q"/><circle class="lhh1z-yfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ring" {...props}></Icon>
