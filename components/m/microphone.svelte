<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dx9ziwb2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dx9ziwb2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:microphone" {...props}></Icon>
