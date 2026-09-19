<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qet9msrbi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qet9msrbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-meteor" {...props}></Icon>
