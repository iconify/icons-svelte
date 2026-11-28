<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/p/puh695b-r.css';
import '../../css/g/gy6t8qprz.css';
import '../../css/e/eyw9bdcdh.css';
import '../../css/d/dmqs4bbjm.css';
import '../../css/v/v6fglctjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="puh695b-r"/><path class="gy6t8qprz"/><path class="eyw9bdcdh"/><path class="dmqs4bbjm"/><path class="v6fglctjz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:penguin" {...props}></Icon>
