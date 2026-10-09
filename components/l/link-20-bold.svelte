<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aghwx5bsq.css';
import '../../css/t/tel8tmb8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="aghwx5bsq"/><path class="tel8tmb8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:link-20-bold" {...props}></Icon>
