<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o93lq-byo.css';
import '../../css/a/amd3c_7ux.css';
import '../../css/w/wjkzsobel.css';
import '../../css/i/ihj7g8l1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><ellipse class="amd3c_7ux"/><path class="wjkzsobel"/><path class="ihj7g8l1o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:cone" {...props}></Icon>
