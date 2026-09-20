<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pm_-v1bpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pm_-v1bpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:hand-cycle" {...props}></Icon>
