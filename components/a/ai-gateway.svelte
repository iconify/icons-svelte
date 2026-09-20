<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jf4qkte-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jf4qkte-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:ai-gateway" {...props}></Icon>
