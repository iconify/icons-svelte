<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ldh3u0amb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ldh3u0amb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:openai-dark" {...props}></Icon>
