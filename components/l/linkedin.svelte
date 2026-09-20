<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_a-jbcwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="l_a-jbcwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:linkedin" {...props}></Icon>
