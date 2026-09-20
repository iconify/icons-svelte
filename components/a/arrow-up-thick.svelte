<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dgfb9-b1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dgfb9-b1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-up-thick" {...props}></Icon>
