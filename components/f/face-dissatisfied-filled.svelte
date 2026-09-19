<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iffb6ably.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="iffb6ably"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:face-dissatisfied-filled" {...props}></Icon>
