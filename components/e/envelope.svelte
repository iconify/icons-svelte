<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qq2hylb_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qq2hylb_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:envelope" {...props}></Icon>
