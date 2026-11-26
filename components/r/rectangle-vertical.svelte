<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/enie18bjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="enie18bjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:rectangle-vertical" {...props}></Icon>
