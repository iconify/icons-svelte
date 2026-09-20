<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q58c3bbto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":257};
const content = `<path class="q58c3bbto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:claude-ai" {...props}></Icon>
