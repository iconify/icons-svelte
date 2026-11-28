<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/g/ga_2bab2s.css';
import '../../css/w/w7_mhrwuu.css';
import '../../css/f/f4c2eobkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ga_2bab2s"/><path class="w7_mhrwuu"/><path class="f4c2eobkp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:calendar-fold" {...props}></Icon>
