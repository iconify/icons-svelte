<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3l8a-bdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="x3l8a-bdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:ms-word-outline" {...props}></Icon>
