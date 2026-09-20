<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ciwla3dbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ciwla3dbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:bug-virus-browser-remix" {...props}></Icon>
