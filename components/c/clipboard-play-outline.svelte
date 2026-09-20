<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pm8b7jchf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pm8b7jchf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clipboard-play-outline" {...props}></Icon>
