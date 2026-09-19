<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3q_3l9wz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="g3q_3l9wz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:multiple-windows" {...props}></Icon>
