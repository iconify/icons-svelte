<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7bk0z64w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="w7bk0z64w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:boulder3" {...props}></Icon>
