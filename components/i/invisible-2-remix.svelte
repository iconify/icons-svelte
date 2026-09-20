<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ou3oexjod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ou3oexjod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:invisible-2-remix" {...props}></Icon>
