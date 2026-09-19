<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxcr60a4i.css';
import '../../css/b/b15_3b_bo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gxcr60a4i"/><path class="b15_3b_bo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:cics-db2-connection" {...props}></Icon>
