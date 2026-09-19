<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9iojhbsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="b9iojhbsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:minus" {...props}></Icon>
