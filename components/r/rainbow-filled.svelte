<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z62-w0m7e.css';
import '../../css/l/l47wg2bol.css';
import '../../css/m/mubrohbof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z62-w0m7e"/><path class="l47wg2bol"/><path class="mubrohbof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:rainbow-filled" {...props}></Icon>
