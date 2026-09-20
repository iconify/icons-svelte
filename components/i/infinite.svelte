<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/il5uuvbmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="il5uuvbmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:infinite" {...props}></Icon>
