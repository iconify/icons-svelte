<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmizg-b1r.css';
import '../../css/w/wuslfeixb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mmizg-b1r"/><path class="wuslfeixb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:faceid-line" {...props}></Icon>
