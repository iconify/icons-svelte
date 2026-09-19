<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ru8mpqtzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ru8mpqtzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:file-pdf-fill-16" {...props}></Icon>
