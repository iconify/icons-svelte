<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-74kyb-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="h-74kyb-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:filter-16" {...props}></Icon>
