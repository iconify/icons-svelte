<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhp-87ykt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nhp-87ykt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cards" {...props}></Icon>
