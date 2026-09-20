<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/u/ugaljkxxq.css';
import '../../css/r/rtwk713ua.css';
import '../../css/g/g5qchsf3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ugaljkxxq"/><path class="rtwk713ua"/><path class="g5qchsf3q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:phone-selfie-front" {...props}></Icon>
