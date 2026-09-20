<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ra5khdb3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ra5khdb3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:loop-right-line" {...props}></Icon>
