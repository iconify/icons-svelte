<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xw5o7jb2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="xw5o7jb2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:bars-3-center-left" {...props}></Icon>
