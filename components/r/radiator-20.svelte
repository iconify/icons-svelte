<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kq6nfxbav.css';
import '../../css/e/eyqb_0bcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kq6nfxbav"/><path class="eyqb_0bcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:radiator-20" {...props}></Icon>
