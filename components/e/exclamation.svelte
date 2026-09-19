<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqjcjh8-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lqjcjh8-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:exclamation" {...props}></Icon>
