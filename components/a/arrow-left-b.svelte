<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xmsnwtbcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xmsnwtbcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:arrow-left-b" {...props}></Icon>
