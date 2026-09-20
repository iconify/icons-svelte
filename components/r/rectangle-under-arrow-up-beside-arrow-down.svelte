<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k81q3hz4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="k81q3hz4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:rectangle-under-arrow-up-beside-arrow-down" {...props}></Icon>
