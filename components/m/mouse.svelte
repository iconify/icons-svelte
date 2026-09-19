<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/jqyziyb5h.css';
import '../../css/e/eeuh5cbrn.css';
import '../../css/t/tcoicyila.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><rect class="jqyziyb5h"/><path clip-rule="evenodd" class="eeuh5cbrn"/><path clip-rule="evenodd" class="tcoicyila"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:mouse" {...props}></Icon>
