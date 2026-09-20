<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dl5ybsbbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dl5ybsbbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:feed" {...props}></Icon>
