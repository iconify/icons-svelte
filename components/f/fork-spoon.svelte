<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gi4p9nbze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="gi4p9nbze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:fork-spoon" {...props}></Icon>
