<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vv7snctli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="vv7snctli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:play-circle-fill-12" {...props}></Icon>
