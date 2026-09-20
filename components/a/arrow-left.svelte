<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s413akbnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="s413akbnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:arrow-left" {...props}></Icon>
