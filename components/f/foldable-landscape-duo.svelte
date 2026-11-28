<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3b8mu3ge.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/w/wwfqf9bjp.css';
import '../../css/r/r2rg25b2s.css';
import '../../css/f/f8dnxibrd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary x3b8mu3ge"/><g class="dt0cm9dhy primary"><path class="wwfqf9bjp"/><path class="r2rg25b2s"/><path class="f8dnxibrd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:foldable-landscape-duo" {...props}></Icon>
