<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dehqt92jf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":16};
const content = `<path class="dehqt92jf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:history" {...props}></Icon>
