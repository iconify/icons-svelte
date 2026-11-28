<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/prbjzkbzo.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/u/uuw1qkbsv.css';
import '../../css/x/xij9k1b5m.css';
import '../../css/c/ck0u8-bhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="prbjzkbzo secondary"/><g class="dt0cm9dhy primary"><path class="uuw1qkbsv"/><path class="xij9k1b5m"/><path class="ck0u8-bhu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:monitor-play-duo" {...props}></Icon>
