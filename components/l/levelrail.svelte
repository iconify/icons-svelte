<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffpz238lq.css';
import '../../css/b/bj_k-fngv.css';
import '../../css/m/m1jzmcc2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<rect class="ffpz238lq"/><rect class="bj_k-fngv"/><rect class="m1jzmcc2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:levelrail" {...props}></Icon>
