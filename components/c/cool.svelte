<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pb2wwnbzj.css';
import '../../css/k/kc5z_3btr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="pb2wwnbzj"/><path class="kc5z_3btr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:cool" {...props}></Icon>
