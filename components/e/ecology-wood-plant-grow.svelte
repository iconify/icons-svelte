<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbmk7ebis.css';
import '../../css/n/nnln5nbkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lbmk7ebis"/><path class="nnln5nbkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:ecology-wood-plant-grow" {...props}></Icon>
