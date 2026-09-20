<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r6r7whmnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r6r7whmnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:perplexity-line" {...props}></Icon>
