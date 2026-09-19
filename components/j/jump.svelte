<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o93lq-byo.css';
import '../../css/l/lwgt0b34p.css';
import '../../css/p/p3gg84b6g.css';
import '../../css/b/b62w8-blj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><path class="lwgt0b34p"/><path class="p3gg84b6g"/><circle class="b62w8-blj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:jump" {...props}></Icon>
