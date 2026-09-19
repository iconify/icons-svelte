<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kq7_hjmyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kq7_hjmyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:arrow-up-left" {...props}></Icon>
