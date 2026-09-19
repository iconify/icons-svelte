<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8k73xbec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="q8k73xbec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:funnel-fill" {...props}></Icon>
