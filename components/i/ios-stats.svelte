<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9vabkbmi.css';
import '../../css/x/xqpsfqrcy.css';
import '../../css/t/t_ee__bsk.css';
import '../../css/l/lpbjt_eld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m9vabkbmi"/><path class="xqpsfqrcy"/><path class="t_ee__bsk"/><path class="lpbjt_eld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-stats" {...props}></Icon>
