<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j05aesb6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="j05aesb6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:feedback-response-solid" {...props}></Icon>
