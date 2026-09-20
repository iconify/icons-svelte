<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iwj-4kzzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iwj-4kzzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:read" {...props}></Icon>
