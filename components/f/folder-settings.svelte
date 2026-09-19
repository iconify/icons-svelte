<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/c/ctq-00ygq.css';
import '../../css/e/ebxpicc9l.css';
import '../../css/j/jk98jeb-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="ctq-00ygq"/><circle class="ebxpicc9l"/><path class="jk98jeb-y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:folder-settings" {...props}></Icon>
