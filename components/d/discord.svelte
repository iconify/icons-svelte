<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/q/q18biqbaz.css';
import '../../css/b/bxn3_jb7p.css';
import '../../css/p/p36kaob0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="q18biqbaz"/><path class="bxn3_jb7p"/><path class="p36kaob0j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:discord" {...props}></Icon>
