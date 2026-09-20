<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wgwq5j0zn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wgwq5j0zn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:microphone" {...props}></Icon>
