<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ge-k3mw8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="ge-k3mw8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:monument-11" {...props}></Icon>
