<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/t/txevfybmf.css';
import '../../css/j/jvmzb_a3a.css';
import '../../css/g/gu7z32rfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="txevfybmf"/><path class="jvmzb_a3a"/><path class="gu7z32rfw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:radio-stereo" {...props}></Icon>
