<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c07jk9b5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c07jk9b5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:panorama-vertical" {...props}></Icon>
