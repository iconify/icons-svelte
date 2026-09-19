<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bju54pz-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="bju54pz-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:drill-expand" {...props}></Icon>
