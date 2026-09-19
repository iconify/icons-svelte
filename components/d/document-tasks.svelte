<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdey06bji.css';
import '../../css/q/qrtsixoyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jdey06bji"/><path class="qrtsixoyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:document-tasks" {...props}></Icon>
