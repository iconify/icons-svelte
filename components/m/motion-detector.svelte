<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ssl6z0rhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ssl6z0rhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:motion-detector" {...props}></Icon>
