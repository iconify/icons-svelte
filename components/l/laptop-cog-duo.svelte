<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/y/yt38y4bnd.css';
import '../../css/v/va4y6ihja.css';
import '../../css/t/t-w02pb9s.css';
import '../../css/m/m-jydibrh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="yt38y4bnd"/><path class="va4y6ihja"/><path clip-rule="evenodd" class="t-w02pb9s"/><path class="m-jydibrh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:laptop-cog-duo" {...props}></Icon>
