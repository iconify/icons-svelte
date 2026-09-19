<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hzj7dl35p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="hzj7dl35p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:reload-stroke-12" {...props}></Icon>
