<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/e43r7kbsl.css';
import '../../css/a/aif1ydb6t.css';
import '../../css/d/d7ih96bcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="e43r7kbsl wm-k"/><path class="aif1ydb6t wm-shine"/><path class="d7ih96bcr wm-shine"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-lunar:avatar-fox" {...props}></Icon>
