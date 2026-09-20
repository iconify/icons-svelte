<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9d093afe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="a9d093afe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:hierarchy-4" {...props}></Icon>
