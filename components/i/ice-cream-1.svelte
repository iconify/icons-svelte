<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/htbvvgq7j.css';
import '../../css/e/edl3wgbnd.css';
import '../../css/q/qyxdovbor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="htbvvgq7j"/><path class="edl3wgbnd"/><path class="qyxdovbor"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:ice-cream-1" {...props}></Icon>
