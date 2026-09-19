<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8bsvibhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="a8bsvibhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:cup" {...props}></Icon>
