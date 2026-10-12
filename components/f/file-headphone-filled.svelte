<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q52pyccnr.css';
import '../../css/j/jmo65nxdc.css';
import '../../css/y/yyu6w0k1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q52pyccnr"/><path class="jmo65nxdc"/><path class="yyu6w0k1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:file-headphone-filled" {...props}></Icon>
