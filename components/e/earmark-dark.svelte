<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/se_9qubxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":180,"height":180};
const content = `<path class="se_9qubxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:earmark-dark" {...props}></Icon>
