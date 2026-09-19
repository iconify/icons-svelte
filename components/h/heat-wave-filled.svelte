<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9ken1ovu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e9ken1ovu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:heat-wave-filled" {...props}></Icon>
