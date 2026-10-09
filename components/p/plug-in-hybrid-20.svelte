<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tr7_wabhq.css';
import '../../css/r/r3nawdb_c.css';
import '../../css/l/lycvo5b0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tr7_wabhq"/><path class="r3nawdb_c"/><path class="lycvo5b0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:plug-in-hybrid-20" {...props}></Icon>
