<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmao38p7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wmao38p7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:button-power-circle-1-remix" {...props}></Icon>
