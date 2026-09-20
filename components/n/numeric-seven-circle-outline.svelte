<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrbquor0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vrbquor0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:numeric-seven-circle-outline" {...props}></Icon>
