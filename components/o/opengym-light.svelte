<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a2j7g4b3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a2j7g4b3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:opengym-light" {...props}></Icon>
