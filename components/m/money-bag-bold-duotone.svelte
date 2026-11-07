<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vt5rq6mfd.css';
import '../../css/r/rce5qmo1y.css';
import '../../css/k/kyu7tx1-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vt5rq6mfd"/><path class="rce5qmo1y"/><path class="kyu7tx1-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:money-bag-bold-duotone" {...props}></Icon>
