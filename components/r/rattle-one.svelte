<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/o/ofg1alwyk.css';
import '../../css/l/lm8wm8y6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><circle transform="rotate(40 29.463 16.989)" class="ofg1alwyk"/><path class="lm8wm8y6h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:rattle-one" {...props}></Icon>
