<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmlna1m4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kmlna1m4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:calendar-sync" {...props}></Icon>
