<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0zwfc1qo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="d0zwfc1qo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:debug-restart-frame" {...props}></Icon>
