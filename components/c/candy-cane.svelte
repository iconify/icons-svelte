<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlnb7obyi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="vlnb7obyi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:candy-cane" {...props}></Icon>
