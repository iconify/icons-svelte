<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f12wigmwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":795,"height":813};
const content = `<path class="f12wigmwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:q-upper-case" {...props}></Icon>
