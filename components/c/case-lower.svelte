<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/p/pzgy2ibzo.css';
import '../../css/i/i9jm-20sb.css';
import '../../css/i/izvhglblk.css';
import '../../css/r/rnnmp6upq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="pzgy2ibzo wm-shadow"/><path class="i9jm-20sb wm-shadow"/><path class="izvhglblk"/><path class="rnnmp6upq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:case-lower" {...props}></Icon>
