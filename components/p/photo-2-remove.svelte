<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5__1z18o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="g5__1z18o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:photo-2-remove" {...props}></Icon>
