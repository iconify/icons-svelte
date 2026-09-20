<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udfoosbol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="udfoosbol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:mirror-horizontally-remix" {...props}></Icon>
