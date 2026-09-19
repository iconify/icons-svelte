<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/m/m-w6wgbel.css';
import '../../css/e/e0ym9q64n.css';
import '../../css/h/hynvvbbxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="m-w6wgbel"/><circle class="e0ym9q64n"/><path class="hynvvbbxd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:baby-mobile" {...props}></Icon>
