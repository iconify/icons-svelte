<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1mcems0k.css';
import '../../css/y/ydsujbbpq.css';
import '../../css/r/r86n_3b9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="l1mcems0k"/><path class="ydsujbbpq"/><path class="r86n_3b9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:house-sun-20-bold" {...props}></Icon>
