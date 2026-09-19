<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2mnc1cer.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="w2mnc1cer"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:folder-blank" {...props}></Icon>
