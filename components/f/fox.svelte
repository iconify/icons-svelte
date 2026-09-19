<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/nzmceyb3d.css';
import '../../css/h/h_t03-bjv.css';
import '../../css/w/wq8363ozr.css';
import '../../css/l/lt7dyxb6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="nzmceyb3d"/><path class="h_t03-bjv"/><path class="wq8363ozr"/><path class="lt7dyxb6b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:fox" {...props}></Icon>
