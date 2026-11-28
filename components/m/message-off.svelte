<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w43jouzpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w43jouzpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:message-off" {...props}></Icon>
