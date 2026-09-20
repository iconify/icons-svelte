<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhla2-b5p.css';
import '../../css/r/r2gwrbc_m.css';
import '../../css/o/olx8frbln.css';
import '../../css/p/p-0gvwbqy.css';
import '../../css/d/dr--31bsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hhla2-b5p"/><path class="r2gwrbc_m"/><path class="olx8frbln"/><path class="p-0gvwbqy"/><path class="dr--31bsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-emojis:musical-score" {...props}></Icon>
