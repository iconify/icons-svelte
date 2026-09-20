<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qguk79b1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qguk79b1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:horizontal-toggle-button-remix" {...props}></Icon>
