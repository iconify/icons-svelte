<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3jht202b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="p3jht202b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:open-envelope-right-with-baht" {...props}></Icon>
