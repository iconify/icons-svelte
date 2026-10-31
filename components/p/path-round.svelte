<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j639pfotf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j639pfotf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:path-round" {...props}></Icon>
