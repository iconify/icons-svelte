<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtvqhhtjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="vtvqhhtjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:home-stroke-12" {...props}></Icon>
