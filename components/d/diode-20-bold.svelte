<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6ni-hbcz.css';
import '../../css/l/l5s65ua6d.css';
import '../../css/k/k0lpkvdrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d6ni-hbcz"/><path class="l5s65ua6d"/><path class="k0lpkvdrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:diode-20-bold" {...props}></Icon>
