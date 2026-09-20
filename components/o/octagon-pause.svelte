<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u9fa5o8gu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u9fa5o8gu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:octagon-pause" {...props}></Icon>
