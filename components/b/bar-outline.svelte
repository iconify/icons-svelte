<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/apdsbhtqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="apdsbhtqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:bar-outline" {...props}></Icon>
