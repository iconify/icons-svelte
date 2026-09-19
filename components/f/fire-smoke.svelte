<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/q/qqsuixb9t.css';
import '../../css/w/w2_lsgbdw.css';
import '../../css/b/bt2my2z8c.css';
import '../../css/j/jvapn4bkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="qqsuixb9t"/><path class="w2_lsgbdw"/><path class="bt2my2z8c"/><path class="jvapn4bkn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:fire-smoke" {...props}></Icon>
