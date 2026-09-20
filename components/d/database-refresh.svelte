<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/leg00xbga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="leg00xbga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:database-refresh" {...props}></Icon>
