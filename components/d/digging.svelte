<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vfo43fa_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="vfo43fa_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:digging" {...props}></Icon>
