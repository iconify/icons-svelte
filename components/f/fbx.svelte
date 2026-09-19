<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rm5lx6bph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":388,"height":512};
const content = `<path class="rm5lx6bph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:fbx" {...props}></Icon>
