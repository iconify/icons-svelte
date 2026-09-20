<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j023hacmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j023hacmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:bag7-filled" {...props}></Icon>
