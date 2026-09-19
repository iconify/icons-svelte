<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/o/ood7b4x1k.css';
import '../../css/i/ia6zp40mg.css';
import '../../css/w/w6ts2tchd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="ood7b4x1k"/><path class="ia6zp40mg"/><path class="w6ts2tchd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:canned-fruit" {...props}></Icon>
