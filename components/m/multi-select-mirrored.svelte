<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jua1gqqhv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="jua1gqqhv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:multi-select-mirrored" {...props}></Icon>
