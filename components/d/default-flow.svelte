<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_kxo3vjf.css';
import '../../css/y/ycj4854jp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="g_kxo3vjf"/><path transform="matrix(125.07186 0 0 96.75291 2539.419 -100217.58)" class="ycj4854jp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:default-flow" {...props}></Icon>
