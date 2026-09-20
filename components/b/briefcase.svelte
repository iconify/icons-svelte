<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bj4rddc0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="bj4rddc0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:briefcase" {...props}></Icon>
