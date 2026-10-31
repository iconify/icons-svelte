<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7p3-mbin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t7p3-mbin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:award-round" {...props}></Icon>
