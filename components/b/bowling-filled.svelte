<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unoxzc18g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="unoxzc18g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:bowling-filled" {...props}></Icon>
