<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mrsrqfkrg.css';
import '../../css/l/lw_rdhb3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mrsrqfkrg"/><path class="lw_rdhb3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:alarm-alt-filled" {...props}></Icon>
