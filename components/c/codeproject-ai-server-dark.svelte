<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v51z47b0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v51z47b0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:codeproject-ai-server-dark" {...props}></Icon>
