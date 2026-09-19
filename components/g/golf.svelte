<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yl4o3acey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="yl4o3acey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:golf" {...props}></Icon>
