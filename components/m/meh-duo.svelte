<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f-ntwsbcy.css';
import '../../css/j/j-5o590-v.css';
import '../../css/o/o33wn7yhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="f-ntwsbcy"/><path class="j-5o590-v"/><path class="o33wn7yhu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:meh-duo" {...props}></Icon>
