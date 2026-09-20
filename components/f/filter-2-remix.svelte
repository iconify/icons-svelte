<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/axu4wiuad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="axu4wiuad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:filter-2-remix" {...props}></Icon>
