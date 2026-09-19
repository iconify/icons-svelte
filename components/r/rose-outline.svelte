<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vgl5x5s_q.css';
import '../../css/x/xa0d2nb-v.css';
import '../../css/v/ve76htc7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vgl5x5s_q"/><path class="xa0d2nb-v"/><path class="ve76htc7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:rose-outline" {...props}></Icon>
