<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zjicgkbfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zjicgkbfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:dynatrace" {...props}></Icon>
