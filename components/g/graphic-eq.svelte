<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vdjyulb7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":432};
const content = `<path class="vdjyulb7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:graphic-eq" {...props}></Icon>
