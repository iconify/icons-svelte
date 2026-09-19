<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/t/tmngr6b0v.css';
import '../../css/o/o6f548blr.css';
import '../../css/m/mmo-88bcm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="tmngr6b0v"/><path class="o6f548blr"/><circle class="mmo-88bcm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:no-shooting" {...props}></Icon>
