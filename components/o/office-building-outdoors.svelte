<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/k/kso8q1vbq.css';
import '../../css/g/g8hf58bbd.css';
import '../../css/a/au437wwib.css';
import '../../css/d/dlgxj6bqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="kso8q1vbq"/><path class="g8hf58bbd"/><path class="au437wwib"/><path class="dlgxj6bqr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:office-building-outdoors" {...props}></Icon>
