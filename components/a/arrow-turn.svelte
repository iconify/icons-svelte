<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/o87de5lat.css';
import '../../css/q/q2hb7y8hf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="o87de5lat"/><path class="q2hb7y8hf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:arrow-turn" {...props}></Icon>
