<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4z_dubpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s4z_dubpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:calendar-filter-outline" {...props}></Icon>
