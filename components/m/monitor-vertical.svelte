<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9h931b0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v9h931b0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:monitor-vertical" {...props}></Icon>
