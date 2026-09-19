<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xkvki4stc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="xkvki4stc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:reminder-time" {...props}></Icon>
