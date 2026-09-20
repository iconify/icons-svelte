<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nbez5bb6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nbez5bb6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:laptop-camera-remix" {...props}></Icon>
