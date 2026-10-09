<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtbad_v3a.css';
import '../../css/z/zlmlrhbpp.css';
import '../../css/w/w_ns1hbzc.css';
import '../../css/n/nhv_i6bfk.css';
import '../../css/v/vra7nyw8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vtbad_v3a"/><path class="zlmlrhbpp"/><path class="w_ns1hbzc"/><path class="nhv_i6bfk"/><path class="vra7nyw8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:key-handover-48-bold" {...props}></Icon>
