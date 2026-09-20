<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ga-o0vbwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ga-o0vbwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex-color:recycle-1-flat" {...props}></Icon>
