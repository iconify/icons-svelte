<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5170fbol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="y5170fbol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:back" {...props}></Icon>
