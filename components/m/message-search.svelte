<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/t/to4dkwksy.css';
import '../../css/m/mhovb8b_p.css';
import '../../css/p/pic7lxbxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="to4dkwksy"/><circle class="mhovb8b_p"/><path class="pic7lxbxy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:message-search" {...props}></Icon>
