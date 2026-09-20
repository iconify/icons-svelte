<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3e989k5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="b3e989k5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:fullscreen" {...props}></Icon>
