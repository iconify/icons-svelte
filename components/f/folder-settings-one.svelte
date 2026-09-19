<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/r/rjn-u5bcv.css';
import '../../css/b/bkd7rf16l.css';
import '../../css/f/f4tcrjb5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="rjn-u5bcv"/><circle class="bkd7rf16l"/><path class="f4tcrjb5t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:folder-settings-one" {...props}></Icon>
