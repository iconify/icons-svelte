<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6zh5ebzg.css';
import '../../css/c/ctmkibhti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="x6zh5ebzg"/><path class="ctmkibhti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:content-cut" {...props}></Icon>
