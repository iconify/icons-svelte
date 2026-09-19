<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6bk2e-by.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x6bk2e-by"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:chevron-double-close" {...props}></Icon>
