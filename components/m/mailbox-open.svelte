<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e84jgebez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e84jgebez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:mailbox-open" {...props}></Icon>
