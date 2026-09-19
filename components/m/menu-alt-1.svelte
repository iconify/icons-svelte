<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l0l45-b3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="l0l45-b3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:menu-alt-1" {...props}></Icon>
