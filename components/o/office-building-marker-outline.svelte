<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nq5t6u07g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nq5t6u07g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:office-building-marker-outline" {...props}></Icon>
