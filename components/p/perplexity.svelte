<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r19xfjg5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r19xfjg5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:perplexity" {...props}></Icon>
