<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iolxe8bdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="iolxe8bdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:justice-hammer" {...props}></Icon>
