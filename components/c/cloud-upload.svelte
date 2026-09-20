<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hy1mwtb3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hy1mwtb3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:cloud-upload" {...props}></Icon>
