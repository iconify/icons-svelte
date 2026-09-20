<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/p0be3bgwo.css';
import '../../css/p/p9tesnssu.css';
import '../../css/e/ep8ejkici.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="p0be3bgwo"/><path class="p9tesnssu"/><path class="ep8ejkici"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:cooperate" {...props}></Icon>
