<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmz_4mbgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dmz_4mbgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:face-dizzy-filled" {...props}></Icon>
