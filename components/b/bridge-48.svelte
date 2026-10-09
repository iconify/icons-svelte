<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_e3wgwgv.css';
import '../../css/t/tgihwabmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="l_e3wgwgv"/><path class="tgihwabmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bridge-48" {...props}></Icon>
