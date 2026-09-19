<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m531q4efy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="m531q4efy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:meh" {...props}></Icon>
