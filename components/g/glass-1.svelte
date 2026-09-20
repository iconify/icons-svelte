<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lsv3emysi.css';
import '../../css/l/lrloqybnl.css';
import '../../css/w/wcftsnbie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="lsv3emysi"/><path class="lrloqybnl"/><path class="wcftsnbie"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber-color:glass-1" {...props}></Icon>
