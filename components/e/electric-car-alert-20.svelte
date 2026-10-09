<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvhhtlbpu.css';
import '../../css/b/b3smm089e.css';
import '../../css/p/puz5jibvr.css';
import '../../css/k/kroofvbxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nvhhtlbpu"/><path class="b3smm089e"/><path class="puz5jibvr"/><path class="kroofvbxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:electric-car-alert-20" {...props}></Icon>
