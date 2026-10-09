<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bz81stb1f.css';
import '../../css/o/o_l2ikyvi.css';
import '../../css/t/tz03pia3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bz81stb1f"/><path class="o_l2ikyvi"/><path class="tz03pia3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:refresh-cw-48-bold" {...props}></Icon>
