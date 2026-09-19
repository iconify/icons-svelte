<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2dnhxblc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="e2dnhxblc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:italic" {...props}></Icon>
