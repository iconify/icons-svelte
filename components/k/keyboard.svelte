<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nyda63bkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nyda63bkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:keyboard" {...props}></Icon>
