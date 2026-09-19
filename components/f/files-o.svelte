<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5t320bgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="x5t320bgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:files-o" {...props}></Icon>
