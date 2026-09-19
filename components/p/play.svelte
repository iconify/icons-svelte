<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/msez2ntih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":585,"height":684};
const content = `<path class="msez2ntih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:play" {...props}></Icon>
