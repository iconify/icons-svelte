<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wlihmg_5w.css';
import '../../css/d/d15p_kz0v.css';
import '../../css/q/qsfdg6bcv.css';
import '../../css/z/z_5a29b5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wlihmg_5w"/><path class="d15p_kz0v"/><path class="qsfdg6bcv"/><path class="z_5a29b5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:peatland-20" {...props}></Icon>
