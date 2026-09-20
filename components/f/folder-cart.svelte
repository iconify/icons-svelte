<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufv-l2b0j.css';
import '../../css/i/ifw64601y.css';
import '../../css/a/a14xeeb5m.css';
import '../../css/e/ezxvopb-u.css';
import '../../css/h/hrp8-jh4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ufv-l2b0j"/><g class="ifw64601y"><circle class="a14xeeb5m"/><circle class="ezxvopb-u"/><path class="hrp8-jh4g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-cart" {...props}></Icon>
