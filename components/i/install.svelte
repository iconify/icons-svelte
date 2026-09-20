<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/vj5eyac4z.css';
import '../../css/x/xp36hhb7e.css';
import '../../css/e/ej04wndpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="vj5eyac4z"/><path class="xp36hhb7e"/><path class="ej04wndpe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:install" {...props}></Icon>
