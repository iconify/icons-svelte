<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5z0mxbls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="z5z0mxbls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:bed" {...props}></Icon>
