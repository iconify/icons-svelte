<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lrqzf1bpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lrqzf1bpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bank-20-bold" {...props}></Icon>
