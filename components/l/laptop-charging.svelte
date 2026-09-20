<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2l9anbld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="k2l9anbld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:laptop-charging" {...props}></Icon>
