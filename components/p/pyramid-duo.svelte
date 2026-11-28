<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2j9rij4x.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/u/ur93yjbpu.css';
import '../../css/w/wwbc-hbfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c2j9rij4x secondary"/><g class="dt0cm9dhy primary"><path class="ur93yjbpu"/><path class="wwbc-hbfx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:pyramid-duo" {...props}></Icon>
