<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vkk06ubis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vkk06ubis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:mozilla" {...props}></Icon>
