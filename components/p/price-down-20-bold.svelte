<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gt6n36bom.css';
import '../../css/k/k6hjx-z6j.css';
import '../../css/i/i-a1w2n6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gt6n36bom"/><path class="k6hjx-z6j"/><path class="i-a1w2n6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:price-down-20-bold" {...props}></Icon>
