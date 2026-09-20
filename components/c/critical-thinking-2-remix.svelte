<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohfms5buh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ohfms5buh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:critical-thinking-2-remix" {...props}></Icon>
