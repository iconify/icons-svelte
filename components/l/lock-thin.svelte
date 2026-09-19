<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/m/m453z0aue.css';
import '../../css/z/zwjimdbzx.css';
import '../../css/p/pd8fwk-xu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="m453z0aue"/><path class="zwjimdbzx"/><path class="pd8fwk-xu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:lock-thin" {...props}></Icon>
