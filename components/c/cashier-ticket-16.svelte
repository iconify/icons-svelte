<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zw-kpqxcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zw-kpqxcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:cashier-ticket-16" {...props}></Icon>
