<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uw2gcb87n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="uw2gcb87n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:american-football" {...props}></Icon>
