<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/toh0lpxph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="toh0lpxph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:circle-slash" {...props}></Icon>
