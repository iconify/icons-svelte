<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ry3pdv7ms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ry3pdv7ms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ppt" {...props}></Icon>
