<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/a/a0xx5x-li.css';
import '../../css/i/iyk_vub8h.css';
import '../../css/i/ieaxcrbun.css';
import '../../css/u/u3k67q4lu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="a0xx5x-li"/><path class="iyk_vub8h"/><path class="ieaxcrbun"/><path class="u3k67q4lu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:car-wash-outline" {...props}></Icon>
