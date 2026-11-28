<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/g/gok39ybkg.css';
import '../../css/c/cw5no1rbj.css';
import '../../css/c/c4420yblp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="gok39ybkg"/><path class="cw5no1rbj"/><path class="c4420yblp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:baseline" {...props}></Icon>
