<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5dhwaboz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="d5dhwaboz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:cursor-click-remix" {...props}></Icon>
