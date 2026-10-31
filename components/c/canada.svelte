<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m__q8jbmq.css';
import '../../css/e/eft4hdbyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="m__q8jbmq"/><path class="eft4hdbyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:canada" {...props}></Icon>
