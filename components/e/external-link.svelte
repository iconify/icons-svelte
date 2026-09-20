<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipx3pgbfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ipx3pgbfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mi:external-link" {...props}></Icon>
