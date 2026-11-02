<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/godna7t4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="godna7t4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:message-circle-code-fill" {...props}></Icon>
