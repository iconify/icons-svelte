<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cf9xbp85n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="cf9xbp85n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:car-under-gabled-roof" {...props}></Icon>
