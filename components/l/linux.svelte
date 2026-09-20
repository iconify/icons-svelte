<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avu4mnt9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="avu4mnt9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:linux" {...props}></Icon>
