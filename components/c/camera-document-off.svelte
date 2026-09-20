<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qeey5wbox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qeey5wbox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:camera-document-off" {...props}></Icon>
