<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fo2m1xbgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fo2m1xbgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:purse-outline" {...props}></Icon>
