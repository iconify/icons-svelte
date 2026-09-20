<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rtfq3bb6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rtfq3bb6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:radio-button-line" {...props}></Icon>
