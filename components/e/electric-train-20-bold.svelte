<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ksqnkb31x.css';
import '../../css/p/pam77ibjf.css';
import '../../css/p/paihgnbuy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ksqnkb31x"/><path class="pam77ibjf"/><path class="paihgnbuy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:electric-train-20-bold" {...props}></Icon>
