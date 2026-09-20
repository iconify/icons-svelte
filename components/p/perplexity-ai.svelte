<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/re5699mtq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="re5699mtq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:perplexity-ai" {...props}></Icon>
