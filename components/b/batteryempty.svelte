<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b4jjlrbbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":768};
const content = `<path class="b4jjlrbbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:batteryempty" {...props}></Icon>
