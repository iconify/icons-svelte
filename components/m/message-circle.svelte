<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xplf97p2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xplf97p2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:message-circle" {...props}></Icon>
