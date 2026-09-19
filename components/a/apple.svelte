<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahq7px0qs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1408,"height":1664};
const content = `<path class="ahq7px0qs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:apple" {...props}></Icon>
