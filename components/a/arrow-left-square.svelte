<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9y-sxz8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="c9y-sxz8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrow-left-square" {...props}></Icon>
