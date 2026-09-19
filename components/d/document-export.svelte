<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qili0cbnj.css';
import '../../css/i/iq65ps9zm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qili0cbnj"/><path class="iq65ps9zm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:document-export" {...props}></Icon>
