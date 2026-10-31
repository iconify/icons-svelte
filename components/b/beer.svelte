<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/m/mn56eubrm.css';
import '../../css/c/cnv66pbtf.css';
import '../../css/j/jbq0mbbpz.css';
import '../../css/u/u3u0yrb0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="mn56eubrm wm-shadow"/><path class="cnv66pbtf wm-shadow"/><path class="jbq0mbbpz"/><path class="u3u0yrb0l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:beer" {...props}></Icon>
