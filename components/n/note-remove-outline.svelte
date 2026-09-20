<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u5t-a2b2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u5t-a2b2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:note-remove-outline" {...props}></Icon>
