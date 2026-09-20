<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhpi9jbet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bhpi9jbet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:message-2-fill" {...props}></Icon>
