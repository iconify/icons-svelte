<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrb10v-km.css';
import '../../css/y/yhs-rpbzu.css';
import '../../css/t/t_aewkbjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xrb10v-km"/><path class="yhs-rpbzu"/><path class="t_aewkbjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ksuite-grids-dark" {...props}></Icon>
