<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/y/y2bh21bwx.css';
import '../../css/b/bsv5quojw.css';
import '../../css/d/dqw2i7ccb.css';
import '../../css/m/mdfze3b9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":27,"height":32};
const content = `<g class="ft5dv1b6b"><path class="y2bh21bwx"/><path class="bsv5quojw"/><path class="dqw2i7ccb"/><path class="mdfze3b9z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ghostty" {...props}></Icon>
