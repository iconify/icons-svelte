<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chm1hdben.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="chm1hdben"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:less-than-equal" {...props}></Icon>
