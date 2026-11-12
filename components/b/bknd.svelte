<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgdewob5q.css';
import '../../css/h/hvhverbjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qgdewob5q"/><path class="hvhverbjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:bknd" {...props}></Icon>
