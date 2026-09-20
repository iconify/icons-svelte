<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u43is9b7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="u43is9b7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:hi-hat-16" {...props}></Icon>
