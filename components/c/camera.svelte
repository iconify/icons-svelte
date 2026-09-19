<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbnkminyz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":960};
const content = `<path class="jbnkminyz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:camera" {...props}></Icon>
