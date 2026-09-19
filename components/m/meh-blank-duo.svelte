<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f-ntwsbcy.css';
import '../../css/z/z5-42obds.css';
import '../../css/a/a8924ab8w.css';
import '../../css/o/oj7sqrthr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="f-ntwsbcy"/><path class="z5-42obds"/><path class="a8924ab8w"/><path class="oj7sqrthr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:meh-blank-duo" {...props}></Icon>
