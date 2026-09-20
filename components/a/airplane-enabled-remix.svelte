<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qane4gfmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qane4gfmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:airplane-enabled-remix" {...props}></Icon>
