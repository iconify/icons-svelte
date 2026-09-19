<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvilx1q3c.css';
import '../../css/r/ri_106bdd.css';
import '../../css/b/b6w1e6bkw.css';
import '../../css/t/te0_flb6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="kvilx1q3c"><path class="ri_106bdd"/><path class="b6w1e6bkw"/><path class="te0_flb6z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:mitsubishi" {...props}></Icon>
