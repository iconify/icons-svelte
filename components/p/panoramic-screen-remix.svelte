<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y33xhl3hv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y33xhl3hv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:panoramic-screen-remix" {...props}></Icon>
