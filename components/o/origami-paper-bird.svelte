<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/nb5a1ubht.css';
import '../../css/o/okhot3btz.css';
import '../../css/m/mdi54bckg.css';
import '../../css/c/chfys9p0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="nb5a1ubht"/><path class="okhot3btz"/><path class="mdi54bckg"/><path class="chfys9p0h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber-color:origami-paper-bird" {...props}></Icon>
