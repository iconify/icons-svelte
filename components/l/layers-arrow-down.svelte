<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/x/x5p80bb3e.css';
import '../../css/z/ztw5k99hi.css';
import '../../css/y/yu9-2bb7w.css';
import '../../css/h/hzehun63j.css';
import '../../css/g/ggu6y8bem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="x5p80bb3e"/><path class="ztw5k99hi"/><path class="yu9-2bb7w"/><path class="hzehun63j"/><path class="ggu6y8bem"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:layers-arrow-down" {...props}></Icon>
