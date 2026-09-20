<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tb1h0rm8o.css';
import '../../css/a/acwejz0_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="tb1h0rm8o"/><path class="acwejz0_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:hand-with-fingers-splayed" {...props}></Icon>
