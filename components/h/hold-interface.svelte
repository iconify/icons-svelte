<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/a/ajyf3nzah.css';
import '../../css/s/sqkeg0bva.css';
import '../../css/y/yb958u6-f.css';
import '../../css/f/f4un4zb0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="ajyf3nzah"/><path class="sqkeg0bva"/><rect class="yb958u6-f"/><path class="f4un4zb0e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:hold-interface" {...props}></Icon>
