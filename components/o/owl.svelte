<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/f/f_i-55w-x.css';
import '../../css/k/kl6xp4spr.css';
import '../../css/a/a31hkfdiu.css';
import '../../css/i/iahmlcbgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><path class="f_i-55w-x"/><path class="kl6xp4spr"/><circle class="a31hkfdiu"/><circle class="iahmlcbgz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:owl" {...props}></Icon>
