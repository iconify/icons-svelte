<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aswp9gckx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aswp9gckx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:link-chain-remix" {...props}></Icon>
