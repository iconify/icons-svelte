<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wfng9b3mo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="wfng9b3mo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:increase-indent-remix" {...props}></Icon>
