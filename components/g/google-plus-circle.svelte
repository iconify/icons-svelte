<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rcnej6jbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="rcnej6jbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:google-plus-circle" {...props}></Icon>
