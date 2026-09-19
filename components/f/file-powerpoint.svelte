<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijfokybpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="ijfokybpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:file-powerpoint" {...props}></Icon>
