<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgy8--9nd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jgy8--9nd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:panoramic-screen-solid" {...props}></Icon>
