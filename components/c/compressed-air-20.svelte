<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-300obtu.css';
import '../../css/w/we0xbxfdt.css';
import '../../css/s/shaiqxb2f.css';
import '../../css/c/clim4d_fk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="o-300obtu"/><path class="we0xbxfdt"/><path class="shaiqxb2f"/><path class="clim4d_fk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:compressed-air-20" {...props}></Icon>
