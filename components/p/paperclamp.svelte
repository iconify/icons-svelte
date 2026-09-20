<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgpqoo4op.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="fgpqoo4op"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:paperclamp" {...props}></Icon>
