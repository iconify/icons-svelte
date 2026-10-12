<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_v0yebin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="j_v0yebin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:connector-stroke-20" {...props}></Icon>
