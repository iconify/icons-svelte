<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3odx4w7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="m3odx4w7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:recruitment-management" {...props}></Icon>
