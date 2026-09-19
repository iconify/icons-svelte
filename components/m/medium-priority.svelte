<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkky_yb9z.css';
import '../../css/b/bvkc79bpm.css';
import '../../css/b/bwdpl5zyw.css';
import '../../css/m/mdaedzcsu.css';
import '../../css/p/p0vj0xbgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dkky_yb9z"/><g class="bvkc79bpm"><circle class="bwdpl5zyw"/><circle class="mdaedzcsu"/><circle class="p0vj0xbgc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:medium-priority" {...props}></Icon>
