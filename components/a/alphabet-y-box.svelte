<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ms_36u3ns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ms_36u3ns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:alphabet-y-box" {...props}></Icon>
