<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ftndcxpdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ftndcxpdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bytesize:file" {...props}></Icon>
