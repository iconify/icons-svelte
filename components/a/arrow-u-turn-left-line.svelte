<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/w/w8trh7b2k.css';
import '../../css/e/euoysnvle.css';
import '../../css/o/orlvbjr0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="w8trh7b2k"/><path class="euoysnvle"/><path class="orlvbjr0y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-u-turn-left-line" {...props}></Icon>
