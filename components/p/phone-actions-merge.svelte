<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/b/blui24bpf.css';
import '../../css/q/q-f4mubqk.css';
import '../../css/i/iztie-bpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="blui24bpf"/><path class="q-f4mubqk"/><path class="iztie-bpa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:phone-actions-merge" {...props}></Icon>
