<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ty8ngujmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ty8ngujmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:graduation-cap-remix" {...props}></Icon>
