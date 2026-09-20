<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gw41_qb9r.css';
import '../../css/o/o0vpernrl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="gw41_qb9r"/><path class="o0vpernrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:map-marker" {...props}></Icon>
