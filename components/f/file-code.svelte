<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/e/e9q6w_2ei.css';
import '../../css/i/i6bjthbsa.css';
import '../../css/j/j0u-0_o-r.css';
import '../../css/s/sq7ldu1vw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="e9q6w_2ei"/><path class="i6bjthbsa"/><path class="j0u-0_o-r"/><path class="sq7ldu1vw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:file-code" {...props}></Icon>
