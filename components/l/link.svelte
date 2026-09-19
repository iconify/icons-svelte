<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/to0c2ub7t.css';
import '../../css/m/mb5m2wb9f.css';
import '../../css/e/eksr6el1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="to0c2ub7t"><path class="mb5m2wb9f"/><path class="eksr6el1o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:link" {...props}></Icon>
