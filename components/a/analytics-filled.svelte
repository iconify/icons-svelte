<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fazjucb0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fazjucb0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:analytics-filled" {...props}></Icon>
