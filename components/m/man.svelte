<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4-atlblr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="r4-atlblr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:man" {...props}></Icon>
