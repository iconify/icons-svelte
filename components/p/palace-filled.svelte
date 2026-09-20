<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5tnvjb5t.css';
import '../../css/t/t-cj0obgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z5tnvjb5t"/><path class="t-cj0obgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:palace-filled" {...props}></Icon>
