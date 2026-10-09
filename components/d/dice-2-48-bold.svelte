<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzp1g281f.css';
import '../../css/u/u32gxcc6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mzp1g281f"/><path class="u32gxcc6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:dice-2-48-bold" {...props}></Icon>
