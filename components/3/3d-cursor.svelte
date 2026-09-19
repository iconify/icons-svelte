<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l322akb3h.css';
import '../../css/j/j6u729bhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="l322akb3h"/><path class="j6u729bhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:3d-cursor" {...props}></Icon>
