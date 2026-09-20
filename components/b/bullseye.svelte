<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umtc5tvss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="umtc5tvss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bullseye" {...props}></Icon>
