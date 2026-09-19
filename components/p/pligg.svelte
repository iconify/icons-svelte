<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zjznslb2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1023};
const content = `<path class="zjznslb2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:pligg" {...props}></Icon>
