<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/v/v2iuv1fmo.css';
import '../../css/k/kctpyacdr.css';
import '../../css/l/l2uwf7bam.css';
import '../../css/b/bjb3nvb0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="v2iuv1fmo"/><path class="kctpyacdr wm-a"/><path class="l2uwf7bam"/><path class="bjb3nvb0o wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:radio-duo" {...props}></Icon>
