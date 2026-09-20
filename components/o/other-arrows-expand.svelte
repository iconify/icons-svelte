<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/ba680n3we.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ba680n3we"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:other-arrows-expand" {...props}></Icon>
