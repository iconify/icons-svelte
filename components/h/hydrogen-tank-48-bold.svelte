<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eroh1ib1d.css';
import '../../css/e/ekmyd2l1t.css';
import '../../css/v/vdkkqgbeg.css';
import '../../css/v/vlrk2yboz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="eroh1ib1d"/><path class="ekmyd2l1t"/><path class="vdkkqgbeg"/><path class="vlrk2yboz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hydrogen-tank-48-bold" {...props}></Icon>
