<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2xsqtgqd.css';
import '../../css/p/pdd2_pbvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="t2xsqtgqd"/><path class="pdd2_pbvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:download-fill-12" {...props}></Icon>
