<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmaxhhb3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wmaxhhb3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:info-circle" {...props}></Icon>
