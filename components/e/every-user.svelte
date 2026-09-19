<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/g/g2e3-xb4j.css';
import '../../css/j/jfgjanxpp.css';
import '../../css/o/oqflbw88g.css';
import '../../css/o/ovtvrgkrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><circle class="g2e3-xb4j"/><circle class="jfgjanxpp"/><circle class="oqflbw88g"/><path class="ovtvrgkrb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:every-user" {...props}></Icon>
