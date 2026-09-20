<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/s/s7ml_zbvx.css';
import '../../css/g/gu4o6xvsl.css';
import '../../css/e/eiee3q-fs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="s7ml_zbvx"/><path class="gu4o6xvsl"/><path class="eiee3q-fs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:cables-usb-1" {...props}></Icon>
