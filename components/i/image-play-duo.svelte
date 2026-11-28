<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twb5ftgbd.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/s/szl-vpbku.css';
import '../../css/l/l3krqn9dm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary twb5ftgbd"/><g class="dt0cm9dhy primary"><path class="szl-vpbku"/><path class="l3krqn9dm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:image-play-duo" {...props}></Icon>
