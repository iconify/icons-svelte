<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_qh4u67n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w_qh4u67n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:perplexity-ai-dark" {...props}></Icon>
