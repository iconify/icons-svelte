<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wy6caez-r.css';
import '../../css/e/es2bfhexf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wy6caez-r"/><path class="es2bfhexf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:panel-left-bold-duotone" {...props}></Icon>
