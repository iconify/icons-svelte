<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kzf2ejbga.css';
import '../../css/o/o21t2h-ii.css';
import '../../css/l/lv-tnswjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kzf2ejbga"/><path class="o21t2h-ii"/><path class="lv-tnswjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mobile-charger-20-bold" {...props}></Icon>
