<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hu_t3tbfu.css';
import '../../css/s/syzt_cbmk.css';
import '../../css/n/n0oj8po7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hu_t3tbfu"/><path class="syzt_cbmk"/><path class="n0oj8po7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:imbalance-20" {...props}></Icon>
