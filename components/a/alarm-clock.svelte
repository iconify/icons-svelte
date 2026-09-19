<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owivm4o1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="owivm4o1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:alarm-clock" {...props}></Icon>
