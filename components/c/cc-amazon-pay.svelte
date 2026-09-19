<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqhkegbrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="pqhkegbrq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:cc-amazon-pay" {...props}></Icon>
