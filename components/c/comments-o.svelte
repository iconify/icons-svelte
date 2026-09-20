<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eckurabwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="eckurabwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:comments-o" {...props}></Icon>
