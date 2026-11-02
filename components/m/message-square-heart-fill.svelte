<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zlh9jvftu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zlh9jvftu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:message-square-heart-fill" {...props}></Icon>
