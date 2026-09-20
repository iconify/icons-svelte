<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-62fle1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="b-62fle1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:elephant" {...props}></Icon>
