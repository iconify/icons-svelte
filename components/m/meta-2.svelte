<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/klya34bbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":65,"height":64};
const content = `<path class="klya34bbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:meta-2" {...props}></Icon>
