<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/msz3ifwoi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="msz3ifwoi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:deez" {...props}></Icon>
