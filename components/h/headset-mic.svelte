<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gb-l3h6li.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gb-l3h6li"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:headset-mic" {...props}></Icon>
