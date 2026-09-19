<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/w1kx2epvq.css';
import '../../css/v/vyh9iac7o.css';
import '../../css/d/d5jhbmbzf.css';
import '../../css/u/u6iipyb0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="w1kx2epvq"/><path class="vyh9iac7o"/><path class="d5jhbmbzf"/><path class="u6iipyb0r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:music-note-list" {...props}></Icon>
