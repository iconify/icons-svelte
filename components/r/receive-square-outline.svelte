<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uo6u187sz.css';
import '../../css/h/hfmquscpz.css';
import '../../css/m/mzfoi9l1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uo6u187sz"/><path class="hfmquscpz"/><path clip-rule="evenodd" class="mzfoi9l1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:receive-square-outline" {...props}></Icon>
