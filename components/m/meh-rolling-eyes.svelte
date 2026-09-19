<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d38hmobbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="d38hmobbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:meh-rolling-eyes" {...props}></Icon>
