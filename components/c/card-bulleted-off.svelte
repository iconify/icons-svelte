<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qq0442bom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qq0442bom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:card-bulleted-off" {...props}></Icon>
