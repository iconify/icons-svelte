<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xdp3vsbnw.css';
import '../../css/a/aqnztv02g.css';
import '../../css/p/pur2tt30n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xdp3vsbnw"/><path class="aqnztv02g"/><path class="pur2tt30n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:full-width-stroke-20" {...props}></Icon>
