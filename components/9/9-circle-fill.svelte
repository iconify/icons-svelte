<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvezambly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="uvezambly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:9-circle-fill" {...props}></Icon>
