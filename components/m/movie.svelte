<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/f/f6q6bbc7u.css';
import '../../css/y/ylp_vncrn.css';
import '../../css/g/gya453bci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="f6q6bbc7u"/><path class="ylp_vncrn"/><path class="gya453bci"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:movie" {...props}></Icon>
