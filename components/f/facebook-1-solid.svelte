<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pgkky5bfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pgkky5bfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:facebook-1-solid" {...props}></Icon>
