<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jo67xg7hi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="jo67xg7hi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:poll-results" {...props}></Icon>
