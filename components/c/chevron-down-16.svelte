<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9n7lz53r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="r9n7lz53r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:chevron-down-16" {...props}></Icon>
