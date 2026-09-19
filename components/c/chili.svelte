<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/x/xkc428b-w.css';
import '../../css/b/b33ifqbsd.css';
import '../../css/g/gtgxb9p8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="xkc428b-w"/><path class="b33ifqbsd"/><path class="gtgxb9p8u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:chili" {...props}></Icon>
