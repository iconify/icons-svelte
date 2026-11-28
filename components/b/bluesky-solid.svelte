<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fki9ziffh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fki9ziffh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:bluesky-solid" {...props}></Icon>
