<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2h60z5xv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="w2h60z5xv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:commercial-11" {...props}></Icon>
