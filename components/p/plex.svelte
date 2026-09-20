<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/opp5y0_jk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="opp5y0_jk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:plex" {...props}></Icon>
