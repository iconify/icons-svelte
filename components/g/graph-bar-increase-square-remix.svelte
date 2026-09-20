<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1rns0b7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="q1rns0b7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:graph-bar-increase-square-remix" {...props}></Icon>
