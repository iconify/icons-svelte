<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ntcc1wbps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ntcc1wbps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:cog-remix" {...props}></Icon>
