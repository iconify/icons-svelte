<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x90fdobfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x90fdobfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:message-square-x" {...props}></Icon>
