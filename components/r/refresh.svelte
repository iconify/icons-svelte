<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/of-adsbxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":631,"height":718};
const content = `<path class="of-adsbxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:refresh" {...props}></Icon>
