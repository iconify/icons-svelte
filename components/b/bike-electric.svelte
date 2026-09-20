<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n175pfqli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n175pfqli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bike-electric" {...props}></Icon>
