<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/k26cw-5bd.css';
import '../../css/t/tnondjiha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="k26cw-5bd"/><path class="tnondjiha"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:arhive-load-fill" {...props}></Icon>
