<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/g5z6obdrt.css';
import '../../css/z/zm_ki8omw.css';
import '../../css/g/g9xmp3kch.css';
import '../../css/m/mo5netbri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="g5z6obdrt"/><path clip-rule="evenodd" class="zm_ki8omw"/><path class="g9xmp3kch"/><path class="mo5netbri"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-print:pill-off" {...props}></Icon>
