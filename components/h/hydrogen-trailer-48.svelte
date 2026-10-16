<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5z7agb-i.css';
import '../../css/l/lrw892zbj.css';
import '../../css/l/l89bje-3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="d5z7agb-i"/><path class="lrw892zbj"/><path class="l89bje-3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hydrogen-trailer-48" {...props}></Icon>
