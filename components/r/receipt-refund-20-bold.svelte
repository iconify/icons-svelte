<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iua8clh6p.css';
import '../../css/n/n_-rgtsiv.css';
import '../../css/q/qbrfddcfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="iua8clh6p"/><path class="n_-rgtsiv"/><path class="qbrfddcfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:receipt-refund-20-bold" {...props}></Icon>
