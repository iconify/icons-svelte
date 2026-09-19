<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/z/z-hi-2qyy.css';
import '../../css/i/il3_yhf-e.css';
import '../../css/z/zkqbqgb3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="z-hi-2qyy"/><circle class="il3_yhf-e"/><path class="zkqbqgb3y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:bread-machine" {...props}></Icon>
