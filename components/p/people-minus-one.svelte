<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/xiq54obrr.css';
import '../../css/g/g0d1dnbiv.css';
import '../../css/t/t8y--cb1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="xiq54obrr"/><path clip-rule="evenodd" class="g0d1dnbiv"/><path class="t8y--cb1d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:people-minus-one" {...props}></Icon>
