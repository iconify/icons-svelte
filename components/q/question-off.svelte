<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/npv9m71la.css';
import '../../css/f/fkksm04zo.css';
import '../../css/y/y4_l99bdm.css';
import '../../css/m/mo5netbri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="npv9m71la"/><path clip-rule="evenodd" class="fkksm04zo"/><path clip-rule="evenodd" class="y4_l99bdm"/><path class="mo5netbri"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:question-off" {...props}></Icon>
