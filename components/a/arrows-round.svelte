<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/xf0iaj41n.css';
import '../../css/b/b51midcrf.css';
import '../../css/h/hq0wmibaf.css';
import '../../css/z/zbpqhxbim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="xf0iaj41n"/><path class="b51midcrf"/><path class="hq0wmibaf"/><path class="zbpqhxbim"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:arrows-round" {...props}></Icon>
