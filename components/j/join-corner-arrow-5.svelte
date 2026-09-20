<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7vk71b4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y7vk71b4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:join-corner-arrow-5" {...props}></Icon>
