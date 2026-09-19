<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6vh3dbqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="y6vh3dbqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:close-filled" {...props}></Icon>
