<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tr7_wabhq.css';
import '../../css/r/r3nawdb_c.css';
import '../../css/y/yl6jnvtmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tr7_wabhq"/><path class="r3nawdb_c"/><path class="yl6jnvtmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:electric-car-20" {...props}></Icon>
