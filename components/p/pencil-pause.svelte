<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vnbpl8blr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vnbpl8blr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:pencil-pause" {...props}></Icon>
