<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zc-zz-dvu.css';
import '../../css/u/uh_772b6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zc-zz-dvu"/><path class="uh_772b6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-z-os-containers" {...props}></Icon>
