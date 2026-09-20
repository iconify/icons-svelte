<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rrx6ypb5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rrx6ypb5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:credit-card-16" {...props}></Icon>
