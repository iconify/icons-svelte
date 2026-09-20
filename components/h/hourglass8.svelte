<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g30le_0ri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="g30le_0ri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:hourglass8" {...props}></Icon>
