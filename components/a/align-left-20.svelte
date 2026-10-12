<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e4vlptxqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="e4vlptxqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:align-left-20" {...props}></Icon>
