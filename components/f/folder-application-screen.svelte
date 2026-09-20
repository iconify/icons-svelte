<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7bbfvb2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="y7bbfvb2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:folder-application-screen" {...props}></Icon>
