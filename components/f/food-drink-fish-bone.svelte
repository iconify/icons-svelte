<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mx5x3u-1w.css';
import '../../css/u/u7gqq6bqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mx5x3u-1w"/><path class="u7gqq6bqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:food-drink-fish-bone" {...props}></Icon>
