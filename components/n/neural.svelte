<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/c/co1jphb4p.css';
import '../../css/n/nd2nnhb9z.css';
import '../../css/d/d-bufxb7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path clip-rule="evenodd" class="co1jphb4p"/><path class="nd2nnhb9z"/><path class="d-bufxb7a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:neural" {...props}></Icon>
