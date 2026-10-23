<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-w-_16dk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e-w-_16dk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:message-circle-text" {...props}></Icon>
