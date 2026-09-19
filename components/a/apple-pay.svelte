<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tb1ht8aoq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tb1ht8aoq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:apple-pay" {...props}></Icon>
