<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5pk2n8fa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e5pk2n8fa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:certification" {...props}></Icon>
