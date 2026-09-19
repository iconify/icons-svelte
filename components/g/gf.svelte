<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/hcoc46qez.css';
import '../../css/i/ijcdvubgt.css';
import '../../css/x/x9okyob9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":24};
const content = `<g class="ft5dv1b6b"><rect class="hcoc46qez"/><path clip-rule="evenodd" class="ijcdvubgt"/><path clip-rule="evenodd" class="x9okyob9o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flagpack:gf" {...props}></Icon>
