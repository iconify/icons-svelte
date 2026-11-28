<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wy4ubgbvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wy4ubgbvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:book-info" {...props}></Icon>
