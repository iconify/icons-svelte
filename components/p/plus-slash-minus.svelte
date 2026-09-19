<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ct5x7jbbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ct5x7jbbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:plus-slash-minus" {...props}></Icon>
