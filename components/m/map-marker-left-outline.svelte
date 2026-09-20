<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aa72s50bh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aa72s50bh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:map-marker-left-outline" {...props}></Icon>
