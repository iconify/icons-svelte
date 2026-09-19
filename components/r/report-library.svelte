<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oo2mek7rm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="oo2mek7rm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:report-library" {...props}></Icon>
