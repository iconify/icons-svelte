<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/duxim6xmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duxim6xmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:halloween-skull-filled" {...props}></Icon>
