<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qg269lhoo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="qg269lhoo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:flower" {...props}></Icon>
