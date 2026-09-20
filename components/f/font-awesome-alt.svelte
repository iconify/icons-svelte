<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fc7quy63x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fc7quy63x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:font-awesome-alt" {...props}></Icon>
