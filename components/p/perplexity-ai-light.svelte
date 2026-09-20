<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/erj7oo6ms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="erj7oo6ms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:perplexity-ai-light" {...props}></Icon>
