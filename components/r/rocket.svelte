<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hpdbnghdn.css';
import '../../css/w/wv9ep6bap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="hpdbnghdn"/><path class="wv9ep6bap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:rocket" {...props}></Icon>
