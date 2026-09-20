<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4jy4ac-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="o4jy4ac-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:layout-window-1" {...props}></Icon>
