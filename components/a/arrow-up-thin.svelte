<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdhpalb9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kdhpalb9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-up-thin" {...props}></Icon>
