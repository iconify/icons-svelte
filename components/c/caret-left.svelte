<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nv9d7-4cb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":192,"height":512};
const content = `<path class="nv9d7-4cb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:caret-left" {...props}></Icon>
