<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fn9dj_esb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fn9dj_esb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:cloud-download-x" {...props}></Icon>
