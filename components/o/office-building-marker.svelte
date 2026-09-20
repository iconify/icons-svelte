<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hoe0bnkcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hoe0bnkcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:office-building-marker" {...props}></Icon>
