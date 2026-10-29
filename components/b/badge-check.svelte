<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqdsmob1w.css';
import '../../css/a/a5q1z5qkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fqdsmob1w wm-k"/><path class="a5q1z5qkn wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:badge-check" {...props}></Icon>
