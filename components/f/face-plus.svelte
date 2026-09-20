<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/v7e-66j0p.css';
import '../../css/l/lr-f1mf1k.css';
import '../../css/c/c12t-giiy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="v7e-66j0p"/><path class="lr-f1mf1k"/><path class="c12t-giiy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:face-plus" {...props}></Icon>
