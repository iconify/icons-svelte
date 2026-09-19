<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txy313exu.css';
import '../../css/t/tvxuj9beq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="txy313exu"/><path class="tvxuj9beq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:house" {...props}></Icon>
