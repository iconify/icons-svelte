<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hy-z4jbjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="hy-z4jbjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:bridge-11" {...props}></Icon>
