<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1_chib4c.css';
import '../../css/u/uw_598fhe.css';
import '../../css/k/k6d-cvqep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="u1_chib4c"/><path class="uw_598fhe"/><path class="k6d-cvqep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:badge-x-20" {...props}></Icon>
