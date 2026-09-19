<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-wc1tbbt.css';
import '../../css/o/ozoz27b5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="k-wc1tbbt"/><path class="ozoz27b5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:chat-bubble-left-right-16-solid" {...props}></Icon>
