<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/upv2lacpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="upv2lacpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:minus-circle" {...props}></Icon>
