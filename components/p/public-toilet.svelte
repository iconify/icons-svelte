<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/t/t7q-hstoq.css';
import '../../css/y/ymiwr7boi.css';
import '../../css/h/hy76pnetd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><circle class="t7q-hstoq"/><circle class="ymiwr7boi"/><path class="hy76pnetd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:public-toilet" {...props}></Icon>
