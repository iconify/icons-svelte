<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1umn1een.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x1umn1een"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:debug-restart" {...props}></Icon>
