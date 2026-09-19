<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ut17l-b_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ut17l-b_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:lightning-in-circle" {...props}></Icon>
