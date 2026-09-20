<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kz07o0bbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":65,"height":64};
const content = `<path class="kz07o0bbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:meta-1" {...props}></Icon>
