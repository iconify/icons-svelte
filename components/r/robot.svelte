<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/s6r87qy8a.css';
import '../../css/n/nzlrb5bjk.css';
import '../../css/g/g6y5ocbly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="s6r87qy8a"/><path class="nzlrb5bjk"/><path class="g6y5ocbly"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:robot" {...props}></Icon>
