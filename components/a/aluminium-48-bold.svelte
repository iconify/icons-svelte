<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nnjw03tfc.css';
import '../../css/s/s76963bxh.css';
import '../../css/z/zo3asy96u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nnjw03tfc"/><path class="s76963bxh"/><path class="zo3asy96u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:aluminium-48-bold" {...props}></Icon>
