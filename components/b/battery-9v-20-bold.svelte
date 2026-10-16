<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2nplbcdb.css';
import '../../css/z/zswjyimei.css';
import '../../css/p/pscvu07cr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="p2nplbcdb"/><path class="zswjyimei"/><path class="pscvu07cr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-9v-20-bold" {...props}></Icon>
