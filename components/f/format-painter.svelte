<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j16d4ujcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="j16d4ujcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:format-painter" {...props}></Icon>
