<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwhlp8bpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="fwhlp8bpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:insertpicture" {...props}></Icon>
