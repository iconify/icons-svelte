<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxn_07btl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oxn_07btl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:eye-focus" {...props}></Icon>
