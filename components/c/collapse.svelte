<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xek9-rddj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":42};
const content = `<path class="xek9-rddj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="topcoat:collapse" {...props}></Icon>
