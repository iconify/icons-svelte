<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqvk9et-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oqvk9et-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:hook" {...props}></Icon>
