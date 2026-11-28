<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whq2bz03s.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/b/bajt83jld.css';
import '../../css/z/zqedzh64t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary whq2bz03s"/><g class="dt0cm9dhy primary"><path class="bajt83jld"/><path class="zqedzh64t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:egg-duo" {...props}></Icon>
