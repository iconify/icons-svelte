<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dfbl99j8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="dfbl99j8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:circle-filled-compact" {...props}></Icon>
