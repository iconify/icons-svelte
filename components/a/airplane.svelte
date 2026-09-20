<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwlaykbzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rwlaykbzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:airplane" {...props}></Icon>
