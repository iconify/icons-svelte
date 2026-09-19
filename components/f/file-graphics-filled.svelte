<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-wqvvv2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="z-wqvvv2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:file-graphics-filled" {...props}></Icon>
