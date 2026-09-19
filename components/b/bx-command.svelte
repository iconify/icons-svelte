<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ua6ey7-at.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ua6ey7-at"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-command" {...props}></Icon>
