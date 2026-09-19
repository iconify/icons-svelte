<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5mlk4bke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="f5mlk4bke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:file-pdf" {...props}></Icon>
