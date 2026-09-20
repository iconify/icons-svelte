<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0ctrg0qy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m0ctrg0qy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:move-file-remix" {...props}></Icon>
