<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/d/d30aez8nr.css';
import '../../css/x/xij1iob8t.css';
import '../../css/v/vjydmy47l.css';
import '../../css/k/kunkzfb7p.css';
import '../../css/o/oe1d-srie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="d30aez8nr"/><path class="xij1iob8t"/><path class="vjydmy47l"/><rect class="kunkzfb7p"/><path class="oe1d-srie"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:gift" {...props}></Icon>
