<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/el9bc6-4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="el9bc6-4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:mv-ai-line" {...props}></Icon>
