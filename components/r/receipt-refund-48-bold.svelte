<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qk4s-jblr.css';
import '../../css/o/o2ddx5b5f.css';
import '../../css/j/jrnu5tbgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qk4s-jblr"/><path class="o2ddx5b5f"/><path class="jrnu5tbgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:receipt-refund-48-bold" {...props}></Icon>
