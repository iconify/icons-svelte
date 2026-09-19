<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdnz6h9tz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="cdnz6h9tz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:linked-database" {...props}></Icon>
