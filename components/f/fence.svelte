<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rflvi0bdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rflvi0bdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:fence" {...props}></Icon>
