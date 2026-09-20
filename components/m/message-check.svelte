<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xenaye8jy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xenaye8jy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:message-check" {...props}></Icon>
