<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tq9n9laxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="tq9n9laxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:pentagon" {...props}></Icon>
