<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nl8v2zbsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nl8v2zbsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:aircon-window" {...props}></Icon>
