<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ix679zbux.css';
import '../../css/l/lh-bp5b_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ix679zbux"/><path class="lh-bp5b_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:procurement-20-bold" {...props}></Icon>
