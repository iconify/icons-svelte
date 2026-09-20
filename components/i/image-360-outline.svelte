<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/no--2obox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="no--2obox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:image-360-outline" {...props}></Icon>
