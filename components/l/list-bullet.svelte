<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0m365bkk.css';
import '../../css/x/x4edefbgr.css';
import '../../css/k/kkxmdkb-g.css';
import '../../css/y/yd79u1b7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="o0m365bkk"/><circle class="x4edefbgr"/><circle class="kkxmdkb-g"/><circle class="yd79u1b7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:list-bullet" {...props}></Icon>
