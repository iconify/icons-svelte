<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2u9jmb8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="t2u9jmb8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:ingot" {...props}></Icon>
