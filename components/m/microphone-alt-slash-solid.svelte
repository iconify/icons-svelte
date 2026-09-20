<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-2chxb9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="f-2chxb9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:microphone-alt-slash-solid" {...props}></Icon>
