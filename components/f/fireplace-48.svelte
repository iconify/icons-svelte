<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8mp0wbzm.css';
import '../../css/w/wkylhn4dt.css';
import '../../css/p/pvx_7s2bb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="m8mp0wbzm"/><path class="wkylhn4dt"/><path class="pvx_7s2bb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fireplace-48" {...props}></Icon>
