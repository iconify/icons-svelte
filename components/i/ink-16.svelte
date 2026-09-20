<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqby3ib5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="tqby3ib5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:ink-16" {...props}></Icon>
