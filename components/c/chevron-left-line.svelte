<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sp6mn7brp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sp6mn7brp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:chevron-left-line" {...props}></Icon>
