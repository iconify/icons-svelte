<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jcsz-kddh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jcsz-kddh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:deaf-solid" {...props}></Icon>
