<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7g2yjbil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v7g2yjbil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:bluesky-filled" {...props}></Icon>
