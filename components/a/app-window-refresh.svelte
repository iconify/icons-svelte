<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xb-1k-83z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xb-1k-83z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:app-window-refresh" {...props}></Icon>
