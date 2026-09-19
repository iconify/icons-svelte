<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qc4wnbbdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qc4wnbbdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:print" {...props}></Icon>
