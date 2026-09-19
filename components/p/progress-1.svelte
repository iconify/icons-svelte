<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nh8kj0bic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000};
const content = `<path class="nh8kj0bic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:progress-1" {...props}></Icon>
