<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qms1rxbvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="qms1rxbvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:picture-in-picture" {...props}></Icon>
