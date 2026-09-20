<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_cyjh5hd.css';
import '../../css/r/r8bd01bug.css';
import '../../css/h/hsksr011x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="n_cyjh5hd"><path class="r8bd01bug"/><path class="hsksr011x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:more-horiz-square-line" {...props}></Icon>
