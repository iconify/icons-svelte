<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7f_54bml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1023};
const content = `<path class="i7f_54bml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:eyeclose" {...props}></Icon>
