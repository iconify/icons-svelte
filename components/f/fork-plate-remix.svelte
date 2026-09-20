<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vha0a8bey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vha0a8bey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:fork-plate-remix" {...props}></Icon>
