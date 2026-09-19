<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/v7a4v0blj.css';
import '../../css/q/qxy5ofb9u.css';
import '../../css/x/xb9-2_4uz.css';
import '../../css/p/pkxzmlbgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><rect class="v7a4v0blj"/><rect class="qxy5ofb9u"/><circle class="xb9-2_4uz"/><path class="pkxzmlbgt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:oven" {...props}></Icon>
