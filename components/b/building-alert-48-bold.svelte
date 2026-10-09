<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pgo-bn5bm.css';
import '../../css/d/dsjehubcj.css';
import '../../css/u/u9s9akrzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pgo-bn5bm"/><path class="dsjehubcj"/><path class="u9s9akrzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:building-alert-48-bold" {...props}></Icon>
