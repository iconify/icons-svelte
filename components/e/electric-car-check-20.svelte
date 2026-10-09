<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvhhtlbpu.css';
import '../../css/b/b3smm089e.css';
import '../../css/p/puz5jibvr.css';
import '../../css/m/mg--uz6gi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nvhhtlbpu"/><path class="b3smm089e"/><path class="puz5jibvr"/><path class="mg--uz6gi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:electric-car-check-20" {...props}></Icon>
