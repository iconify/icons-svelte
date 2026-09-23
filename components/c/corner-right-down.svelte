<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a21l97byt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a21l97byt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:corner-right-down" {...props}></Icon>
