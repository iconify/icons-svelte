<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xv8czdbir.css';
import '../../css/t/ti_zwx44j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xv8czdbir"/><path class="ti_zwx44j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:create" {...props}></Icon>
