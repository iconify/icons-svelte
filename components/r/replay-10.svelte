<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4l7e-bpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="j4l7e-bpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:replay-10" {...props}></Icon>
