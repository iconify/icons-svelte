<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvsghrbxx.css';
import '../../css/h/hxj4a-h4s.css';
import '../../css/p/p_x9mhh4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cvsghrbxx"/><path class="hxj4a-h4s"/><path class="p_x9mhh4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:filestore" {...props}></Icon>
