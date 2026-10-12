<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mc1v07kwj.css';
import '../../css/y/y8ppixbeg.css';
import '../../css/o/omi4i4cer.css';
import '../../css/n/n9nesubig.css';
import '../../css/j/j55tojl3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mc1v07kwj"/><path class="y8ppixbeg"/><path class="omi4i4cer"/><path class="n9nesubig"/><path class="j55tojl3t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:file-pen-duotone" {...props}></Icon>
