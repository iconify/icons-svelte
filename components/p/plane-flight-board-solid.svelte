<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xcveprb9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xcveprb9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:plane-flight-board-solid" {...props}></Icon>
