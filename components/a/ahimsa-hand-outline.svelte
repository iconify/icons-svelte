<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tiohwqvoh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="tiohwqvoh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:ahimsa-hand-outline" {...props}></Icon>
