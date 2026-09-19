<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2j_6wewx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1568,"height":1824};
const content = `<path class="r2j_6wewx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:grapes" {...props}></Icon>
