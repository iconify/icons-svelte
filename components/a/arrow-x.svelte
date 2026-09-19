<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6bj7ybmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="w6bj7ybmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:arrow-x" {...props}></Icon>
