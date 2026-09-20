<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ax_k84bni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ax_k84bni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:envelope" {...props}></Icon>
