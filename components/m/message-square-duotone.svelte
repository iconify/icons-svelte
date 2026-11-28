<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m89f5kbev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m89f5kbev primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:message-square-duotone" {...props}></Icon>
