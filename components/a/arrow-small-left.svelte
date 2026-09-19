<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/teeimabmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="teeimabmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:arrow-small-left" {...props}></Icon>
