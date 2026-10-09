<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tr7_wabhq.css';
import '../../css/r/r3nawdb_c.css';
import '../../css/z/z0q4lw36b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tr7_wabhq"/><path class="r3nawdb_c"/><path class="z0q4lw36b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:car-20" {...props}></Icon>
