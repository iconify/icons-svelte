<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pph593bkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="pph593bkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:fold" {...props}></Icon>
