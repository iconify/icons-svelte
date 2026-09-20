<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9bgbabwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b9bgbabwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:battery-1-filled" {...props}></Icon>
