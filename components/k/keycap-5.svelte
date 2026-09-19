<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/t00mv8b2d.css';
import '../../css/f/ffwe9xbuc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":33};
const content = `<g class="ft5dv1b6b"><path class="t00mv8b2d"/><path class="ffwe9xbuc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:keycap-5" {...props}></Icon>
