<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrcz0db9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="nrcz0db9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:prison-11" {...props}></Icon>
