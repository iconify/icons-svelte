<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amj4c2nxb.css';
import '../../css/a/aeedgejmb.css';
import '../../css/k/k9lxbgstm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="amj4c2nxb"/><path class="aeedgejmb"/><path class="k9lxbgstm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:flow-meter-20-bold" {...props}></Icon>
