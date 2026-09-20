<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/eub-owb9l.css';
import '../../css/b/bnr386b3y.css';
import '../../css/o/omtfbmb6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="eub-owb9l"/><path class="bnr386b3y"/><path clip-rule="evenodd" class="omtfbmb6c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rocket-bold" {...props}></Icon>
