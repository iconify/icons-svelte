<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6yzllbtl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e6yzllbtl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:graduation-cap-round" {...props}></Icon>
