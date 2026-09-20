<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fnaizab9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="fnaizab9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:droplet-with-greek-cross" {...props}></Icon>
