<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcd4puj4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pcd4puj4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:browser-code-2-remix" {...props}></Icon>
