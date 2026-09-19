<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cq4qxab3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":497,"height":512};
const content = `<path class="cq4qxab3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:lark" {...props}></Icon>
