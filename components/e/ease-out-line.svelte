<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m40kpbgfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m40kpbgfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ease-out-line" {...props}></Icon>
