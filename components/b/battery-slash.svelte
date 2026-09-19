<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pt_uxyb5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pt_uxyb5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:battery-slash" {...props}></Icon>
