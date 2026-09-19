<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzyfxg1lm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rzyfxg1lm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:gift" {...props}></Icon>
