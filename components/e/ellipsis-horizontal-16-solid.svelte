<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrlytoj6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xrlytoj6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:ellipsis-horizontal-16-solid" {...props}></Icon>
