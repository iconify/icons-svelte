<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/w/wjzajobpc.css';
import '../../css/w/whu8gg7-e.css';
import '../../css/n/nd3hq4prs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="wjzajobpc"/><path class="whu8gg7-e"/><circle transform="matrix(-1 0 0 1 21 16)" class="nd3hq4prs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:cricket-bat" {...props}></Icon>
