<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbyi9vbqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jbyi9vbqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:droplet" {...props}></Icon>
