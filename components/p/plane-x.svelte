<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rde28zbag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rde28zbag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:plane-x" {...props}></Icon>
