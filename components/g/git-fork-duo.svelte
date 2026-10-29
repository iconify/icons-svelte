<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/p/ph4rgbc9q.css';
import '../../css/a/abs9vim9l.css';
import '../../css/n/ndg34cbdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ph4rgbc9q"/><path class="abs9vim9l"/><path class="ndg34cbdd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:git-fork-duo" {...props}></Icon>
