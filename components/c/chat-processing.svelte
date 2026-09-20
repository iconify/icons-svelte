<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hh0w-acse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="hh0w-acse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:chat-processing" {...props}></Icon>
