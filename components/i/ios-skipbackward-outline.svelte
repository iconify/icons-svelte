<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqkalragn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gqkalragn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-skipbackward-outline" {...props}></Icon>
