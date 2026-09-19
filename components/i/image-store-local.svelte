<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xffjfs7fd.css';
import '../../css/l/ldwjonb-f.css';
import '../../css/q/q0e0esbtj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xffjfs7fd"/><path class="ldwjonb-f"/><path class="q0e0esbtj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:image-store-local" {...props}></Icon>
