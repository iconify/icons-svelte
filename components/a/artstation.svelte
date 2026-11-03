<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhz-90b4r.css';
import '../../css/g/gfbw707kv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="yhz-90b4r"/><path class="gfbw707kv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:artstation" {...props}></Icon>
