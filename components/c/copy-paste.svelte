<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1lo6xjdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="y1lo6xjdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:copy-paste" {...props}></Icon>
