<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihsbtvbdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ihsbtvbdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:fingernail-polished" {...props}></Icon>
