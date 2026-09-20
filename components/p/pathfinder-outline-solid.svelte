<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vv42esbjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vv42esbjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:pathfinder-outline-solid" {...props}></Icon>
