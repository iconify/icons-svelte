<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2zey2evm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="r2zey2evm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:chat" {...props}></Icon>
