<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dw8v8rm4n.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/w/w4bsiacjh.css';
import '../../css/z/z7me5tbpt.css';
import '../../css/g/gznd2dtud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="dw8v8rm4n"/><g class="jn8qy4bru"><path class="w4bsiacjh"/><path class="z7me5tbpt"/></g><path class="gznd2dtud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:mahjong-red-dragon" {...props}></Icon>
