<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/u/uaf3_62mx.css';
import '../../css/a/av9l1ko1u.css';
import '../../css/b/basw9ubgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="uaf3_62mx"/><path class="av9l1ko1u"/><path class="basw9ubgc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:iwatch" {...props}></Icon>
