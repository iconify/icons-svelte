<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o93lq-byo.css';
import '../../css/a/aimf4ebuf.css';
import '../../css/c/c6vox3all.css';
import '../../css/t/tfpzyrb-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><path clip-rule="evenodd" class="aimf4ebuf"/><path class="c6vox3all"/><path class="tfpzyrb-p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:detection" {...props}></Icon>
