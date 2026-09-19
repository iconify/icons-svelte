<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/c7--sybwr.css';
import '../../css/f/fdj6d59ge.css';
import '../../css/w/w1b_bmazf.css';
import '../../css/b/brolgrb2c.css';
import '../../css/u/u7k7a9bky.css';
import '../../css/d/dy6aub64p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="c7--sybwr"/><path class="fdj6d59ge"/><circle class="w1b_bmazf"/><circle class="brolgrb2c"/><circle class="u7k7a9bky"/><path class="dy6aub64p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:cat" {...props}></Icon>
