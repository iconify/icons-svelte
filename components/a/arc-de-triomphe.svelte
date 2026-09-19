<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/s/sceen7deg.css';
import '../../css/y/yikp5ibxa.css';
import '../../css/k/kyp5fljps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="sceen7deg"/><path class="yikp5ibxa"/><path class="kyp5fljps"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:arc-de-triomphe" {...props}></Icon>
