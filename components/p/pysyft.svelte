<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dg6a0ckqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dg6a0ckqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:pysyft" {...props}></Icon>
