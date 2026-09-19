<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8xj_quvl.css';
import '../../css/h/hqconcbne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="h8xj_quvl"/><path class="hqconcbne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:kubelet" {...props}></Icon>
