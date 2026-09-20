<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bk1cacbgq.css';
import '../../css/w/whi2f_bck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="bk1cacbgq"/><path class="whi2f_bck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:island-2" {...props}></Icon>
