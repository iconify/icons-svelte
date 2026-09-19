<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/j/jtu7ayv-p.css';
import '../../css/c/c-lptrhzz.css';
import '../../css/o/ore9ccbul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path clip-rule="evenodd" class="jtu7ayv-p"/><path class="c-lptrhzz"/><path class="ore9ccbul"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:delete-themes" {...props}></Icon>
