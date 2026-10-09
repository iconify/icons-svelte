<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wrrfucygy.css';
import '../../css/k/k_lu-3vpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wrrfucygy"/><path class="k_lu-3vpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-half-20-bold" {...props}></Icon>
