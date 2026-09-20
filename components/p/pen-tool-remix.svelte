<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwrtx0vnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lwrtx0vnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:pen-tool-remix" {...props}></Icon>
