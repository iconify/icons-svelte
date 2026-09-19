<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u21022btp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="u21022btp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:fish1-happy" {...props}></Icon>
