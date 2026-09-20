<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xa4j5f3rn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xa4j5f3rn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:ladder" {...props}></Icon>
