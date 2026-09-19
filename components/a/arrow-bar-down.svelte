<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vo449e5to.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vo449e5to"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:arrow-bar-down" {...props}></Icon>
